<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eabl2c-zp.css';
import '../../css/l/lncpo0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eabl2c-zp"/><path class="lncpo0b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:coins" {...props}></Icon>
