<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhttojxeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhttojxeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-1-sharp-fill" {...props}></Icon>
