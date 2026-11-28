<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs3gkc0he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs3gkc0he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-commit" {...props}></Icon>
