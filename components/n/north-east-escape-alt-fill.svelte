<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4gxo_bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4gxo_bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-east-escape-alt-fill" {...props}></Icon>
