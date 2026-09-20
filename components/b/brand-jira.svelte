<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rqmue42ie.css';
import '../../css/d/dk6z82bvg.css';
import '../../css/v/vvl6uk22v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rqmue42ie"/><path class="dk6z82bvg"/><path class="vvl6uk22v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-jira" {...props}></Icon>
