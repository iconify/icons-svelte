<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjzxuveym.css';
import '../../css/f/foygadfek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qjzxuveym"/><path class="foygadfek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:modal-list" {...props}></Icon>
