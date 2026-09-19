<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymlejsi7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymlejsi7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reload-circle-sharp" {...props}></Icon>
