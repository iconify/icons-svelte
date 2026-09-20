<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/amxs67rqb.css';
import '../../css/t/ty7516ydb.css';
import '../../css/t/t_f65iten.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amxs67rqb"/><circle class="ty7516ydb"/><circle class="t_f65iten"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:percent" {...props}></Icon>
