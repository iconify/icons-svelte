<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcj1yhvjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcj1yhvjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-many-to-one-or-many" {...props}></Icon>
