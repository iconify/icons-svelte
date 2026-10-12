<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/icip4dbvn.css';
import '../../css/q/qdu8wjber.css';
import '../../css/b/b6lm5ubhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="icip4dbvn"/><path class="qdu8wjber"/><path clip-rule="evenodd" class="b6lm5ubhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:newspaper-duotone" {...props}></Icon>
