<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac4r5ub6d.css';
import '../../css/l/lwgbjb0jl.css';
import '../../css/f/fjpj-53lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac4r5ub6d"/><path class="lwgbjb0jl"/><path class="fjpj-53lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-shell" {...props}></Icon>
