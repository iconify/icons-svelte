<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/d/da3r7lk0q.css';
import '../../css/c/cq9m21bdq.css';
import '../../css/o/omcq2obdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="da3r7lk0q"/><path class="cq9m21bdq"/><path class="omcq2obdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:haml" {...props}></Icon>
