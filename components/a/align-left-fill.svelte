<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlrg2jwsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlrg2jwsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-left-fill" {...props}></Icon>
