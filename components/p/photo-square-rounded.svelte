<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/ur7rt5fas.css';
import '../../css/e/eg76xwbic.css';
import '../../css/j/jno4cqb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur7rt5fas"/><path class="eg76xwbic"/><path class="jno4cqb6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-square-rounded" {...props}></Icon>
