<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avdx2ebrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avdx2ebrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:livejournal-logo-block" {...props}></Icon>
