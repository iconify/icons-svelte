<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjk9rcuob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjk9rcuob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:greptile" {...props}></Icon>
