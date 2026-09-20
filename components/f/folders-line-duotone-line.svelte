<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eivil5x4j.css';
import '../../css/a/acg_ub67k.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGMdgKseHX"><g class="ft5dv1b6b"><path class="eivil5x4j"/><path class="acg_ub67k"/></g></mask></defs><path mask="url(#SVGMdgKseHX)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folders-line-duotone-line" {...props}></Icon>
