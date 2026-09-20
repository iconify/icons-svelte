<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6xsmtrch.css';
import '../../css/d/dhs8qrwgp.css';
import '../../css/t/t-ux4n71u.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGvUPw8b1c"><g class="ft5dv1b6b"><path class="x6xsmtrch"/><path class="dhs8qrwgp"/><path class="t-ux4n71u"/></g></mask></defs><path mask="url(#SVGvUPw8b1c)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bag-duotone-line" {...props}></Icon>
