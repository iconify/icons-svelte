<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku175bbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku175bbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:garden" {...props}></Icon>
