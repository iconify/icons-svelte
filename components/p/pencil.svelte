<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udkn3mb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="udkn3mb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:pencil" {...props}></Icon>
