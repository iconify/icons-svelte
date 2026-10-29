<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp6ze3bac.css';
import '../../css/h/h-gnu7brs.css';
import '../../css/u/uh-othbsr.css';
import '../../css/u/uilal2b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp6ze3bac wm-k"/><path class="h-gnu7brs wm-a"/><path class="uh-othbsr wm-k"/><path class="uilal2b1e wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:maximize" {...props}></Icon>
