<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3lbi6bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g3lbi6bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:allergens-gluten-remix" {...props}></Icon>
