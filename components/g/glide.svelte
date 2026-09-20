<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao8yx6wuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao8yx6wuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:glide" {...props}></Icon>
