<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/c/crhqw7b7l.css';
import '../../css/g/g048xd03g.css';
import '../../css/e/e0hfau-no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="crhqw7b7l"/><path class="g048xd03g"/><path class="e0hfau-no"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-alt" {...props}></Icon>
