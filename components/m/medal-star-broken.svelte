<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/acejusade.css';
import '../../css/y/y4qe-ubzy.css';
import '../../css/v/v7q1lwidl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="acejusade"/><path class="y4qe-ubzy"/><path class="v7q1lwidl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-broken" {...props}></Icon>
