<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb4nkgcdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb4nkgcdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:delete" {...props}></Icon>
