<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kihydrb9x.css';
import '../../css/s/s1r84oshw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kihydrb9x"/><path class="s1r84oshw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:moon-duotone" {...props}></Icon>
