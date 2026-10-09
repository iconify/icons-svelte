<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j83z96bud.css';
import '../../css/s/sqs7l1bjm.css';
import '../../css/z/znfqzbt2u.css';
import '../../css/b/bxzxb8v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j83z96bud"/><path class="sqs7l1bjm"/><path class="znfqzbt2u"/><path class="bxzxb8v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-alert-48" {...props}></Icon>
