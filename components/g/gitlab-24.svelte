<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kquo5_p3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kquo5_p3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gitlab-24" {...props}></Icon>
