<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/s5qf56fne.css';
import '../../css/j/jxl67pbry.css';
import '../../css/r/r2l1z561j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="s5qf56fne"/><circle class="jxl67pbry"/><circle class="r2l1z561j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:ellipsis" {...props}></Icon>
