<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhscw0hrm.css';
import '../../css/k/k0dg-7b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhscw0hrm"/><path class="k0dg-7b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:blast" {...props}></Icon>
