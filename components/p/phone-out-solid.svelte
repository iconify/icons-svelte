<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu-d01bjj.css';
import '../../css/n/nm2dxfjpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu-d01bjj"/><path class="nm2dxfjpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-out-solid" {...props}></Icon>
