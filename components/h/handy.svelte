<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1xyw2e6j.css';
import '../../css/q/qi-a3ui-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1xyw2e6j"/><path class="qi-a3ui-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:handy" {...props}></Icon>
