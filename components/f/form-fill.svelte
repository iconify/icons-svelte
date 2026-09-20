<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl4cpsbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl4cpsbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:form-fill" {...props}></Icon>
