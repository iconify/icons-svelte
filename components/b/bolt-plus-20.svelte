<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9dzyiszx.css';
import '../../css/d/d1u5dmb3x.css';
import '../../css/o/oduy0uyli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="d1u5dmb3x"/><path class="oduy0uyli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-plus-20" {...props}></Icon>
