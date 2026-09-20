<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr43w4bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr43w4bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:angle-double-down" {...props}></Icon>
