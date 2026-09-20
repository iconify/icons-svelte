<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-8enguzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-8enguzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-circle-line" {...props}></Icon>
