<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-e6xd29v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q-e6xd29v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:bank" {...props}></Icon>
