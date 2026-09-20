<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/varr8acvu.css';
import '../../css/n/nk4n3vbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="varr8acvu"/><path class="nk4n3vbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-file-adobe-bold" {...props}></Icon>
