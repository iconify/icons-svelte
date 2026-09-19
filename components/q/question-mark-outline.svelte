<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6y_ocbap.css';
import '../../css/d/duuf9m24f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6y_ocbap"/><circle class="duuf9m24f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:question-mark-outline" {...props}></Icon>
