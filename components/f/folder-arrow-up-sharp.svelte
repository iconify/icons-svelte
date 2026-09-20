<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3zkowdqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3zkowdqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-arrow-up-sharp" {...props}></Icon>
