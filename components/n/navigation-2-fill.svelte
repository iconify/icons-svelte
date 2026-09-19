<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fidnqcqve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fidnqcqve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:navigation-2-fill" {...props}></Icon>
