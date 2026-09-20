<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eamdc-byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eamdc-byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:imdb-logo" {...props}></Icon>
