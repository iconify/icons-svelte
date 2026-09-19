<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbgoen-2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbgoen-2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:healthcare-nlp-api" {...props}></Icon>
