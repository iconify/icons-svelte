<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlp5iacha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlp5iacha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:itunes-logo-solid" {...props}></Icon>
