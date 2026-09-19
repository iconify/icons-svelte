<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn-6xjbzp.css';
import '../../css/t/tk3rezb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dn-6xjbzp"/><path class="tk3rezb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:primitive" {...props}></Icon>
