<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9vm7jbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9vm7jbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:behance-logo" {...props}></Icon>
