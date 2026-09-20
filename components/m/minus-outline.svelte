<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-f93bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-f93bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:minus-outline" {...props}></Icon>
