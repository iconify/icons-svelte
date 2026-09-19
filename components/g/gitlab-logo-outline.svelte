<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unu9fbpdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gitlab-logo-outline"><path class="(Stroke) Vector unu9fbpdc" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:gitlab-logo-outline" {...props}></Icon>
