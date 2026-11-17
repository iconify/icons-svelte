<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h8_j8s5yy.css';
import '../../css/y/y9k2wv5xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h8_j8s5yy"/><rect class="y9k2wv5xs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cinema" {...props}></Icon>
