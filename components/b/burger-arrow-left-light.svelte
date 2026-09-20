<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9lsbzb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9lsbzb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-left-light" {...props}></Icon>
