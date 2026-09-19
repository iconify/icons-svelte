<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k65h5h91a.css';
import '../../css/d/dtgkx25td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k65h5h91a"/><path class="dtgkx25td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:bootstrapping" {...props}></Icon>
