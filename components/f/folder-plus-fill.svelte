<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0tcmt9kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0tcmt9kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-plus-fill" {...props}></Icon>
