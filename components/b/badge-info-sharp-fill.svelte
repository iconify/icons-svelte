<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw2l8obpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw2l8obpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-info-sharp-fill" {...props}></Icon>
