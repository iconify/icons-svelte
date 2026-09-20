<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zqj5b0nts.css';
import '../../css/c/crpkpxbgp.css';
import '../../css/w/wh8wwcoah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zqj5b0nts"/><path class="crpkpxbgp"/><circle class="wh8wwcoah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:credit-card-light" {...props}></Icon>
