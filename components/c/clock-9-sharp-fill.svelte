<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn14jqb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kn14jqb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-9-sharp-fill" {...props}></Icon>
