<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2iskrb7m.css';
import '../../css/y/y8vjolbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2iskrb7m"/><path clip-rule="evenodd" class="y8vjolbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:grid-on-fill" {...props}></Icon>
