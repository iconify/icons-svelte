<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eme4hnzwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eme4hnzwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-up-double" {...props}></Icon>
