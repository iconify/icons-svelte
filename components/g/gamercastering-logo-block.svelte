<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv8e7ibdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cv8e7ibdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gamercastering-logo-block" {...props}></Icon>
