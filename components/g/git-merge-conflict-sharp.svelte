<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnmbmdbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnmbmdbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-merge-conflict-sharp" {...props}></Icon>
