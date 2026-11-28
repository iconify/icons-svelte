<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-udccci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-udccci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:factory-check" {...props}></Icon>
