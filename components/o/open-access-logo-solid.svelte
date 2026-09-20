<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m01rnsbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m01rnsbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:open-access-logo-solid" {...props}></Icon>
