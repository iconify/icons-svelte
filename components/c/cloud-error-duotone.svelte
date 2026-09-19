<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gs25nqb9b.css';
import '../../css/k/km66jmbju.css';
import '../../css/a/amcqfubsz.css';
import '../../css/o/o3rus7b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gs25nqb9b"/><path class="km66jmbju"/><path class="amcqfubsz"/><path class="o3rus7b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-error-duotone" {...props}></Icon>
