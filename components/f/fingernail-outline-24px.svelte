<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtw2qxriw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtw2qxriw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fingernail-outline-24px" {...props}></Icon>
