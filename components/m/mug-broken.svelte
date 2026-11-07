<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f_18xcbpp.css';
import '../../css/a/ab9oag7th.css';
import '../../css/n/n5gy6sdjs.css';
import '../../css/j/jlzv4qbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f_18xcbpp"/><path class="ab9oag7th"/><path class="n5gy6sdjs"/><path class="jlzv4qbob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-broken" {...props}></Icon>
