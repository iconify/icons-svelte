<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9v9jiznd.css';
import '../../css/z/z1pqwacjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f9v9jiznd"/><path class="z1pqwacjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-coffee-cup" {...props}></Icon>
