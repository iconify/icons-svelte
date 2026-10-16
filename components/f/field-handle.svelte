<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my6kgdczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my6kgdczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:field-handle" {...props}></Icon>
