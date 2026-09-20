<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6l-kpbwa.css';
import '../../css/n/ngq2artnh.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/jdn1rvbrs.css';
import '../../css/a/aukz7zd6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g6l-kpbwa"/><path class="ngq2artnh"/><g class="jn8qy4bru"><path class="jdn1rvbrs"/><path class="aukz7zd6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:onion" {...props}></Icon>
