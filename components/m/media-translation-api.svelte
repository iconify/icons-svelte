<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-b0m2bdx.css';
import '../../css/m/m7ak63tdr.css';
import '../../css/h/hjqeyxbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-b0m2bdx"/><path class="m7ak63tdr"/><path class="hjqeyxbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:media-translation-api" {...props}></Icon>
