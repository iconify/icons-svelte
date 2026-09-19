<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plwc2obrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plwc2obrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:book-open-fill" {...props}></Icon>
