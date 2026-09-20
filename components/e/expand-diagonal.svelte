<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpidyrg8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpidyrg8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-diagonal" {...props}></Icon>
