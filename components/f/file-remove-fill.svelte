<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qudtiwuyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qudtiwuyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:file-remove-fill" {...props}></Icon>
