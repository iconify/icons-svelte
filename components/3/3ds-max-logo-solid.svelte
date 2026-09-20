<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv0rs1cdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv0rs1cdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:3ds-max-logo-solid" {...props}></Icon>
