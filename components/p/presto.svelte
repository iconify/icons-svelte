<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnts90b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnts90b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:presto" {...props}></Icon>
