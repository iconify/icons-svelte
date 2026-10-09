<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9dzyiszx.css';
import '../../css/g/g8-7we8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="g8-7we8zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-check-20" {...props}></Icon>
