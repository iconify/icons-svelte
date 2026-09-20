<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeleeyw0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeleeyw0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:physotherapist" {...props}></Icon>
