<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya4cjjcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya4cjjcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circles-sharp-fill" {...props}></Icon>
