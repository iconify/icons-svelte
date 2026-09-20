<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1629e8zl.css';
import '../../css/n/npbkqyb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1629e8zl"/><path class="npbkqyb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install-mobile-filled" {...props}></Icon>
