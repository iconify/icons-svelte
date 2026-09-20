<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ivi_x117u.css';
import '../../css/n/npzbi206w.css';
import '../../css/m/m-2o9kbye.css';
import '../../css/p/pd4xfeb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="ivi_x117u"/><circle class="npzbi206w"/><circle class="m-2o9kbye"/><path class="pd4xfeb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-queen" {...props}></Icon>
