<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v25mscwtj.css';
import '../../css/y/ywqsk4bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v25mscwtj"/><path class="ywqsk4bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanboard" {...props}></Icon>
