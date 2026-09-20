<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bugtqh3mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bugtqh3mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:design-bump-logo-block" {...props}></Icon>
