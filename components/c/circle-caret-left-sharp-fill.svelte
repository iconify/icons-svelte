<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5sqdxj-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5sqdxj-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-caret-left-sharp-fill" {...props}></Icon>
