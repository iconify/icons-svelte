<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nas3ou1jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nas3ou1jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-bookmark" {...props}></Icon>
