<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x49svmbsw.css';
import '../../css/d/d510u6bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x49svmbsw"/><path class="d510u6bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:combobox" {...props}></Icon>
