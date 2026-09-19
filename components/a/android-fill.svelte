<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsweqxb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsweqxb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:android-fill" {...props}></Icon>
