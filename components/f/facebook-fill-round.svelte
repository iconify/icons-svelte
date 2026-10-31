<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eptx6fbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eptx6fbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:facebook-fill-round" {...props}></Icon>
