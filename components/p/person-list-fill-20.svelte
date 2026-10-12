<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4butrblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s4butrblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-list-fill-20" {...props}></Icon>
