<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8utjoj0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8utjoj0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-diagonal" {...props}></Icon>
