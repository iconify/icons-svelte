<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w09qfhb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w09qfhb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:minus-light" {...props}></Icon>
