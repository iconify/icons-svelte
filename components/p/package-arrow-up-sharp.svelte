<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o46lr6boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o46lr6boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-arrow-up-sharp" {...props}></Icon>
