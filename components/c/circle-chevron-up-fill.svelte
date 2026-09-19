<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii0ewyw5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ii0ewyw5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevron-up-fill" {...props}></Icon>
