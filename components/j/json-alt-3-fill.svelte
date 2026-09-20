<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2t895bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2t895bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-3-fill" {...props}></Icon>
