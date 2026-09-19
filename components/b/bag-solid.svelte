<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi0qeri7g.css';
import '../../css/a/a_bjixb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi0qeri7g"/><path class="a_bjixb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:bag-solid" {...props}></Icon>
