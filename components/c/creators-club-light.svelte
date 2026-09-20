<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs5ix9gtg.css';
import '../../css/s/s3kax5bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs5ix9gtg"/><path class="s3kax5bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:creators-club-light" {...props}></Icon>
