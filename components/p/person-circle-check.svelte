<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjn0y42br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kjn0y42br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-circle-check" {...props}></Icon>
