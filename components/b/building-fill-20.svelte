<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_6gdx37i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_6gdx37i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-fill-20" {...props}></Icon>
