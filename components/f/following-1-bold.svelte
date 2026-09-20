<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2obrw9uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2obrw9uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:following-1-bold" {...props}></Icon>
