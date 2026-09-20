<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo7urvgho.css';
import '../../css/s/s5nareudl.css';
import '../../css/j/jfk9ubm9c.css';
import '../../css/i/i5oonfbxc.css';
import '../../css/i/i2n_2vb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="oo7urvgho"/><circle class="s5nareudl"/><circle class="jfk9ubm9c"/><path clip-rule="evenodd" class="i5oonfbxc"/><path class="i2n_2vb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:group-fill" {...props}></Icon>
