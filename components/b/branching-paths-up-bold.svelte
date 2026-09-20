<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo-j0bcdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo-j0bcdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:branching-paths-up-bold" {...props}></Icon>
