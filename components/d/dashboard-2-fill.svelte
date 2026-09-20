<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkiqt7bnd.css';
import '../../css/k/k06qbne_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkiqt7bnd"/><path class="k06qbne_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-2-fill" {...props}></Icon>
