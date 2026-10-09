<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v454e9bix.css';
import '../../css/j/jjdvkvbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v454e9bix"/><path class="jjdvkvbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-commit-20" {...props}></Icon>
