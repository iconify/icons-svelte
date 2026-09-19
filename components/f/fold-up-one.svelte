<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxotp5bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oxotp5bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fold-up-one" {...props}></Icon>
