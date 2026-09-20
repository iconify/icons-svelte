<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fnf6pdbdu.css';
import '../../css/g/gp0egaclj.css';
import '../../css/e/e2nq-yvbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnf6pdbdu"/><circle class="gp0egaclj"/><path class="e2nq-yvbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:git-commit-vertical" {...props}></Icon>
